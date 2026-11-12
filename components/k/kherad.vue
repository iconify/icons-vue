<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrxewtok.css';
import '../../css/v/vukg9z6-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbrxewtok"/><path class="vukg9z6-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kherad" /></template>
