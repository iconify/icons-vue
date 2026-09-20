<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h37jq-dsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h37jq-dsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-from-down-bracket" /></template>
