<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fut96rbkh.css';
import '../../css/w/waobp-biz.css';
import '../../css/v/v5ifasbxi.css';
import '../../css/f/fb9fhtmzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fut96rbkh"/><path class="waobp-biz"/><path class="v5ifasbxi"/><path class="fb9fhtmzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-contacts" /></template>
