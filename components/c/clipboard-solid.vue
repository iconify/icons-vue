<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3eno4b5g.css';
import '../../css/b/b2gz5jqgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3eno4b5g"/><path class="b2gz5jqgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:clipboard-solid" /></template>
