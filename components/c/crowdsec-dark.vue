<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg2ies3lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bg2ies3lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdsec-dark" /></template>
