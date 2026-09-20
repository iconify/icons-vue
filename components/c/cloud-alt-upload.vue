<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc2fcx.css';
import '../../css/v/v1m4oy.css';
import '../../css/s/so-from-60.css';
import '../../css/d/d-6uh96y.css';
import '../../css/d/d-t2f-vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2fcx"/><path class="v1m4oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-upload" /></template>
