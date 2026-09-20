<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c670tn77z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c670tn77z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eye-closed-solid" /></template>
