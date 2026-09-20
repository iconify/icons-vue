<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipihkyb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipihkyb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ldap-light" /></template>
