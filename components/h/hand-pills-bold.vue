<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw-l5b1k.css';
import '../../css/o/osatibboq.css';
import '../../css/o/ooq4xdh-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw-l5b1k"/><path class="osatibboq"/><path class="ooq4xdh-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-pills-bold" /></template>
