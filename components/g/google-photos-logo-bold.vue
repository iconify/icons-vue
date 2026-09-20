<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmzf_cekc.css';
import '../../css/y/yybosibpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmzf_cekc"/><path class="yybosibpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-photos-logo-bold" /></template>
