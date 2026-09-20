<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g__iqeb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g__iqeb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:khoj-light" /></template>
