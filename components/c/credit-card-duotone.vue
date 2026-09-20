<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beoipcbng.css';
import '../../css/t/tba9ohb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beoipcbng"/><path class="tba9ohb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:credit-card-duotone" /></template>
