<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0awb8bkd.css';
import '../../css/e/ejcigpbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0awb8bkd"/><path class="ejcigpbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:engagement-light" /></template>
