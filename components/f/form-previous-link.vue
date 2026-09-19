<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdp5r-bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp5r-bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-previous-link" /></template>
