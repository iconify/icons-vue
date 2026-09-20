<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aspthzbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aspthzbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-tab-manager-logo-solid" /></template>
