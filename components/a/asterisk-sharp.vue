<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3yrkpbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3yrkpbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:asterisk-sharp" /></template>
