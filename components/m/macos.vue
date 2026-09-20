<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsdbl8bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsdbl8bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:macos" /></template>
