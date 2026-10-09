<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-4rqjbfm.css';
import '../../css/a/aw6b_uyup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-4rqjbfm"/><path class="aw6b_uyup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacity-48-bold" /></template>
