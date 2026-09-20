<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/banr10v6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="banr10v6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eye-closed-outline" /></template>
