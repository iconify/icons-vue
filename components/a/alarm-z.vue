<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d86adob8w.css';
import '../../css/b/bvt239bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d86adob8w"/><path class="bvt239bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-z" /></template>
