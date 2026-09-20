<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vctvmtjcb.css';
import '../../css/a/a6eo7ib1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vctvmtjcb"/><path class="a6eo7ib1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynamodb-dashboard" /></template>
