<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bem5i2brp.css';
import '../../css/c/cohp0c6uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bem5i2brp"/><path class="cohp0c6uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ice-cream-outline" /></template>
