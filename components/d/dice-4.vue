<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9p44xvrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p9p44xvrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:dice-4" /></template>
