<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5jc2bad.css';
import '../../css/r/rjuy8dl9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5jc2bad"/><path class="rjuy8dl9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-bold-duotone" /></template>
