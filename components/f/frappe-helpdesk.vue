<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbmsbj1ug.css';
import '../../css/m/m0hpcl8zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbmsbj1ug"/><path class="m0hpcl8zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-helpdesk" /></template>
