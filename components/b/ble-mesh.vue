<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdy4kbc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdy4kbc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ble-mesh" /></template>
