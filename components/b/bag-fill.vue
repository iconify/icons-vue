<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbvbu5csx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mbvbu5csx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bag-fill" /></template>
