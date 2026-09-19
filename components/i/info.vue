<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkj31zcws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj31zcws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:info" /></template>
