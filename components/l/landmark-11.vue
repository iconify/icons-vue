<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bay3adb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="bay3adb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landmark-11" /></template>
