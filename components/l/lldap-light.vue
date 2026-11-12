<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk_3vtbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jk_3vtbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lldap-light" /></template>
