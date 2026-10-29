<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szku-lbwj.css';
import '../../css/z/zij8omb8i.css';
import '../../css/y/yt0_-0n4r.css';
import '../../css/n/n91xhwb1p.css';
import '../../css/n/nyvku37ko.css';
import '../../css/f/fa26uhbxk.css';
import '../../css/t/tfp12mwnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szku-lbwj wm-shadow"/><path class="wm-k zij8omb8i"/><path class="wm-k yt0_-0n4r"/><path class="n91xhwb1p wm-k"/><path class="nyvku37ko wm-k"/><path class="fa26uhbxk wm-k"/><path class="tfp12mwnq wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-left-right" /></template>
