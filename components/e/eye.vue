<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt1hgbkfu.css';
import '../../css/t/tlvy8hbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt1hgbkfu"/><path class="tlvy8hbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:eye" /></template>
