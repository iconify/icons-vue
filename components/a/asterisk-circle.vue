<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em9343utn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="em9343utn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:asterisk-circle" /></template>
