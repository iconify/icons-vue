<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq0bqacml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq0bqacml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-lock-open-alt" /></template>
