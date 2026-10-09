<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twfn9u9ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="twfn9u9ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bat-20" /></template>
