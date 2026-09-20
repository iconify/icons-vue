<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgangomwz.css';
import '../../css/d/d1ft4ebeo.css';
import '../../css/d/dn6qqpqrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hgangomwz"/><path class="d1ft4ebeo"/><path class="dn6qqpqrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-contacts-light" /></template>
