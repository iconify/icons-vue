<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btp7u209s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btp7u209s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:intercom" /></template>
