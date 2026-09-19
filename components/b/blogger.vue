<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mff0z4bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":990.933,"height":1000};
const content = `<path class="mff0z4bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:blogger" /></template>
