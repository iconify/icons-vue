<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbwe7mc1r.css';
import '../../css/k/kj3l2zbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fbwe7mc1r"/><path class="kj3l2zbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:idiophone-16" /></template>
