<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m85fekbws.css';
import '../../css/z/z6n_ozb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m85fekbws"/><path class="z6n_ozb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-social-services" /></template>
