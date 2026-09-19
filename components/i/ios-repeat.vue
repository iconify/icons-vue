<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvc87pa5f.css';
import '../../css/o/os561700d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvc87pa5f"/><path class="os561700d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-repeat" /></template>
