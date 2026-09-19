<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trmplo9ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="trmplo9ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:do-not-bleach" /></template>
