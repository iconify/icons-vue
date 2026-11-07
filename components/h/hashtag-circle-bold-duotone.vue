<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdvcwidb.css';
import '../../css/g/gjmvk5b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path clip-rule="evenodd" class="gjmvk5b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-circle-bold-duotone" /></template>
