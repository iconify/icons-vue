<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/x/x5ao8m.css';
import '../../css/y/y4wbml.css';
import '../../css/n/nl7ecg.css';
import '../../css/g/ge04hr.css';
import '../../css/k/k4fugd.css';
import '../../css/p/pi14pi.css';
import '../../css/s/so-from-4.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-0_3.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew x5ao8m y4wbml"/><path class="iw1iew nl7ecg"/><path class="ge04hr iw1iew y4wbml"/><path class="iw1iew k4fugd y4wbml"/><path class="iw1iew pi14pi y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bell-alert-twotone" /></template>
