<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br-3rw75n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br-3rw75n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:collabora-online" /></template>
