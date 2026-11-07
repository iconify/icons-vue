<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy2y5qfqd.css';
import '../../css/v/v3iz6x59v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2y5qfqd"/><path class="v3iz6x59v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-minus-bold-duotone" /></template>
