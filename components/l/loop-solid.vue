<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmhmpac7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qmhmpac7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:loop-solid" /></template>
