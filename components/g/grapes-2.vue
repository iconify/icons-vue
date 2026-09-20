<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5tlv01gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t5tlv01gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:grapes-2" /></template>
