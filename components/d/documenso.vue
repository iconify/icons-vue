<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe2_ycbjb.css';
import '../../css/f/ft_gti1us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe2_ycbjb"/><path class="ft_gti1us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:documenso" /></template>
