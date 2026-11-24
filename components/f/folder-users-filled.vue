<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpcwsfbtq.css';
import '../../css/x/xv4mh2pto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpcwsfbtq"/><path class="xv4mh2pto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-users-filled" /></template>
