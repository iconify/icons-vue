<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepvs8ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pepvs8ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:input-latin-capital-letters-filled" /></template>
