<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udnf14b2t.css';
import '../../css/x/xz4g601-d.css';
import '../../css/d/ddxxdn1gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udnf14b2t wm-k"/><path class="wm-k xz4g601-d"/><path class="ddxxdn1gm wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:egg" /></template>
