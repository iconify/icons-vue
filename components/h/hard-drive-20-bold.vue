<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epfqiub8e.css';
import '../../css/b/bx-ljfbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="epfqiub8e"/><path class="bx-ljfbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-drive-20-bold" /></template>
