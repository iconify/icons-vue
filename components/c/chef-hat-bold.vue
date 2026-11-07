<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb-bq1nyz.css';
import '../../css/l/lofqyubof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb-bq1nyz"/><path class="lofqyubof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-bold" /></template>
