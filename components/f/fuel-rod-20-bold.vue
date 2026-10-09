<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p169fcb-f.css';
import '../../css/z/z26u7ebdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p169fcb-f"/><path class="z26u7ebdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-rod-20-bold" /></template>
