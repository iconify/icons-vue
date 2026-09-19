<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu1frrbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu1frrbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-raised-solid" /></template>
