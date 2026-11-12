<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljh46-15w.css';
import '../../css/p/p9i-ec0lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljh46-15w"/><path class="p9i-ec0lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flux-operator-dark" /></template>
