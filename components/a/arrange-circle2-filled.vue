<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpol2ubiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpol2ubiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrange-circle2-filled" /></template>
