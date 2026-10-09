<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw4336b9k.css';
import '../../css/p/phnyk0rqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw4336b9k"/><path class="phnyk0rqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bbq-48" /></template>
