<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx52wrbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx52wrbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:birthday" /></template>
