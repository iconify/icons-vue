<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkuf35_tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkuf35_tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-square-rounded-filled" /></template>
