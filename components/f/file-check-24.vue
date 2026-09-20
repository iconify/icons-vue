<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8f6-zbvd.css';
import '../../css/m/mg23doo2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8f6-zbvd"/><path class="mg23doo2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-check-24" /></template>
