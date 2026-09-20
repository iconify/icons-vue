<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcv7dgnpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcv7dgnpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hdhomerun-light" /></template>
