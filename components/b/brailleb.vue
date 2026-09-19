<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd82jkdcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="gd82jkdcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleb" /></template>
