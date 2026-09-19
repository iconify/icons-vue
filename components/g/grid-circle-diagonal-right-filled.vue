<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3ehty72y.css';
import '../../css/n/neukm1fuz.css';
import '../../css/g/gtn46m-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ehty72y"/><rect class="neukm1fuz"/><rect class="gtn46m-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-diagonal-right-filled" /></template>
