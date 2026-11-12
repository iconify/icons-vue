<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6q28_uum.css';
import '../../css/d/d_om27bee.css';
import '../../css/v/vcwntabdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6q28_uum"/><path class="d_om27bee"/><path class="vcwntabdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-portal-dark" /></template>
