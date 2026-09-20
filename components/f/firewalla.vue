<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjs8erx3y.css';
import '../../css/c/cwxu7xb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjs8erx3y"/><path class="cwxu7xb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firewalla" /></template>
