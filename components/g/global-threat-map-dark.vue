<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_0rlkxdi.css';
import '../../css/k/kiwyvcbue.css';
import '../../css/v/vieb4jbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_0rlkxdi"/><circle class="kiwyvcbue"/><circle class="vieb4jbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:global-threat-map-dark" /></template>
