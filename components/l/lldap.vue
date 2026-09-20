<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk8c4eb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8c4eb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lldap" /></template>
