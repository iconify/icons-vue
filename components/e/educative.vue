<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3_mw7w9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3_mw7w9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:educative" /></template>
