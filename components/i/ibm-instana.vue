<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3diwob9a.css';
import '../../css/x/xjwfqkbgp.css';
import '../../css/x/xtul77bpd.css';
import '../../css/b/byvfoh51a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s3diwob9a"/><circle class="xjwfqkbgp"/><circle class="xtul77bpd"/><path class="byvfoh51a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-instana" /></template>
