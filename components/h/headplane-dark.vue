<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b89dqjg6u.css';
import '../../css/h/h9o14dbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b89dqjg6u"/><path class="h9o14dbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headplane-dark" /></template>
