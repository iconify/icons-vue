<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-y_ncckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-y_ncckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-cyrillic" /></template>
