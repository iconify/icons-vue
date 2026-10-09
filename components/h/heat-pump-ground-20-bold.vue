<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huo95kxbo.css';
import '../../css/t/txu8yubls.css';
import '../../css/a/arzvezb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="huo95kxbo"/><path class="txu8yubls"/><path class="arzvezb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-ground-20-bold" /></template>
