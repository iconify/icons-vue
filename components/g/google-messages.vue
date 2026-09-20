<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvw901bjd.css';
import '../../css/k/k468snbzm.css';
import '../../css/r/rqpbbk94c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvw901bjd"/><path class="k468snbzm"/><path class="rqpbbk94c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-messages" /></template>
