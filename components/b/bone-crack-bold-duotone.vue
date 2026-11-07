<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-m5ubxc.css';
import '../../css/d/dn1u2whmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-m5ubxc"/><path class="dn1u2whmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-crack-bold-duotone" /></template>
