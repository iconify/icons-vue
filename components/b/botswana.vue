<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw-97iyer.css';
import '../../css/a/az4h9ufdp.css';
import '../../css/p/pc91ydrlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="rw-97iyer"/><path class="az4h9ufdp"/><path class="pc91ydrlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:botswana" /></template>
