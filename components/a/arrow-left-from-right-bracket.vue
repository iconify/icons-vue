<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s29wwbcwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s29wwbcwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left-from-right-bracket" /></template>
