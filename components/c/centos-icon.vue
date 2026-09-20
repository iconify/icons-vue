<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hnpslxbvn"/><path class="v-zezabkj"/><path class="znouh4rfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:centos-icon" /></template>
<style>
.hnpslxbvn {
  fill: var(--svg-color--a14f8c, #a14f8c);
  d: path("M161.12 251.609c68.267-18.292 108.78-88.462 90.488-156.73C233.316 26.614 163.146-13.9 94.879 4.393C26.613 22.684-13.9 92.854 4.392 161.121s88.462 108.78 156.729 90.488");
}

.v-zezabkj {
  fill: var(--svg-color--fff, #fff);
  d: path("M128 31.159L99.634 59.524l-40.111-.003l-.003 40.114L31.156 128l28.364 28.363l.001 40.115l40.113-.002L128 224.842l28.363-28.366l40.116-.002l-.002-40.11L224.844 128l-28.37-28.363l-40.112-40.111zm8.61 28.363v30.602L128 98.733l-8.61-8.61V59.525zM85.663 73.49l21.64 21.641l.003 12.172l-12.179.003L73.49 85.665zm-26.144 45.9h30.603l8.609 8.61l-8.61 8.609H59.52zm105.667 0h30.602v17.219h-30.602l-8.61-8.61zm-69.57 28.817h12.175v12.174l-21.639 21.64l-12.175-12.176zm52.593-.002l12.173.002l21.639 21.638l-12.175 12.175l-21.64-21.639zm-20.21 8.37l8.61 8.61v30.602h-17.22v-30.602z");
}

.znouh4rfj {
  fill: var(--svg-color--efa724, #efa724);
  d: path("M136.609 108.218L128 115.826l-8.609-7.611v11.176h-11.175l7.609 8.609l-7.611 8.61h11.177v11.173l8.609-7.608l8.609 7.609V136.61h11.173l-7.607-8.609l7.61-8.61h-11.176zm19.778-48.668l13.945 13.945l-21.64 21.639l.001 12.174h12.174l21.64-21.638L196.5 99.663l-.022-40.138z");
}

</style>
