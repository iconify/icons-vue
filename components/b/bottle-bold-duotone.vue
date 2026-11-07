<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig8ga7b3p.css';
import '../../css/r/r-u6g9bnb.css';
import '../../css/s/s1gudszho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig8ga7b3p"/><path class="r-u6g9bnb"/><path class="s1gudszho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bottle-bold-duotone" /></template>
