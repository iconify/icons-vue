<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzjm_3bmj.css';
import '../../css/v/vun6ubbjw.css';
import '../../css/e/eyqpwsbyt.css';
import '../../css/o/o12pcgbwf.css';
import '../../css/i/i-07h4bkh.css';
import '../../css/i/i-ke3gyiz.css';
import '../../css/w/wqstgm7-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzjm_3bmj"/><path class="vun6ubbjw"/><path class="eyqpwsbyt"/><path class="o12pcgbwf"/><path class="i-07h4bkh"/><path class="i-ke3gyiz"/><path class="wqstgm7-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-barcode-outline" /></template>
