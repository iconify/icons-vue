<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmg665juo.css';
import '../../css/o/odwst6b3m.css';
import '../../css/h/hb1bi3sso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg665juo"/><rect class="odwst6b3m"/><rect class="hb1bi3sso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-horizontal-start-filled" /></template>
