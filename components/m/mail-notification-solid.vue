<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ectnb4k.css';
import '../../css/t/ti-3o5bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ectnb4k"/><path class="ti-3o5bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-notification-solid" /></template>
