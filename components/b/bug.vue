<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlerm3brg.css';
import '../../css/m/mgar0-gjb.css';
import '../../css/z/zmfqa13ae.css';
import '../../css/p/puphvnb0h.css';
import '../../css/i/idjc4pbow.css';
import '../../css/l/lkzo6fybb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hlerm3brg"/><path class="mgar0-gjb"/><path class="zmfqa13ae"/><path class="puphvnb0h"/><path class="idjc4pbow"/><path class="lkzo6fybb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bug" /></template>
