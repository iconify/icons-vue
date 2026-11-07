<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqdm2xbfi.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/f/fhxzx1b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqdm2xbfi"/><path class="x41xvfi0c"/><path clip-rule="evenodd" class="fhxzx1b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-circle-outline" /></template>
