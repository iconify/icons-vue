<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxb4qkbhf.css';
import '../../css/i/ivphhvj4r.css';
import '../../css/p/p4rsgjvps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oxb4qkbhf"/><path clip-rule="evenodd" class="ivphhvj4r"/><path class="p4rsgjvps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jack-locked-16" /></template>
