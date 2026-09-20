<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg6jjtbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qg6jjtbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-right-circle-solid" /></template>
