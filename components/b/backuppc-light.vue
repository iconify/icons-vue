<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em14apxum.css';
import '../../css/g/gdwzp4r6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="em14apxum"/><path class="gdwzp4r6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backuppc-light" /></template>
