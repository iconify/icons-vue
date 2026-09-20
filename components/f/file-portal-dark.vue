<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6q28_uum.css';
import '../../css/q/q2kzgfbfr.css';
import '../../css/n/nyo26bcbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6q28_uum"/><path class="q2kzgfbfr"/><path class="nyo26bcbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-portal-dark" /></template>
