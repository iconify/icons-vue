<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cld0m4bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="cld0m4bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:entrance-11" /></template>
