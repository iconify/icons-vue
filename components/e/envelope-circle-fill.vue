<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqh9-2boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tqh9-2boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-circle-fill" /></template>
