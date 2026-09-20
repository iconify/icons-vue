<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eff8rj4kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eff8rj4kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bug" /></template>
