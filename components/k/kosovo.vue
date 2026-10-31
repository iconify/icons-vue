<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8dybub9u.css';
import '../../css/u/utquofbms.css';
import '../../css/z/zbsqqabff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="e8dybub9u"/><path class="utquofbms"/><path class="zbsqqabff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:kosovo" /></template>
