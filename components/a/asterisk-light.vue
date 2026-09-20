<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipu4fx39x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipu4fx39x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:asterisk-light" /></template>
