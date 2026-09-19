<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvj36pv6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mvj36pv6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:flask" /></template>
