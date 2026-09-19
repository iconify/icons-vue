<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btuo36bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="btuo36bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dry-in-the-shade" /></template>
