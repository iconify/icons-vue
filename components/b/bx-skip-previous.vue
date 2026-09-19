<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn1ytrb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn1ytrb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-skip-previous" /></template>
