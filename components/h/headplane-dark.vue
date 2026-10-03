<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b89dqjg6u.css';
import '../../css/s/s39gonhkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b89dqjg6u"/><path class="s39gonhkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headplane-dark" /></template>
