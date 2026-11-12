<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0zrdacze.css';
import '../../css/y/ytt2rub5i.css';
import '../../css/x/x0ucnnbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0zrdacze"/><path class="ytt2rub5i"/><path class="x0ucnnbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kmeet-light" /></template>
