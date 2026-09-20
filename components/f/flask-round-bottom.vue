<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br14ndb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br14ndb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-round-bottom" /></template>
