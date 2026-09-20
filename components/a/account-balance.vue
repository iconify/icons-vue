<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sftp1mbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sftp1mbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-balance" /></template>
