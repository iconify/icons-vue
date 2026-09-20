<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rs57i1bci"/><path class="vbxe0xtoi"/><path class="rrc1qo91i"/><g class="egu5g0_em"><path class="rw87kq9db"/><path class="btr5hgbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-iraq" /></template>
<style>
.btr5hgbio {
  d: path("M10.716 21.132a.267.267 0 1 1-.533-.001a.267.267 0 0 1 .533.001");
}

.egu5g0_em {
  fill: var(--svg-color--007a3c, #007a3c);
}

.rrc1qo91i {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.rs57i1bci {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4H0z");
}

.rw87kq9db {
  d: path("M11.227 18.06v1.229h5.651v-.737c0-.328-.369-.308-.369-.062v.552h-4.423v-.86l3.102-3.102l.471.501l-2.815 2.846h2.928s.133-.86.931-.86l.912.635v2.314h-8.23s-.205 1.085-1.454.941c0 0 .86-.573.86-1.249c0-.675-.552-1.208-.552-1.208l.778-.491s.082.42.164.542c.083.122.389.235.389.235h1.044l-.014-.546l-.151-.065zm8.302 1.002l-.166.227h-.487c.002-1.151.006-3.418-.001-3.441c-.01-.031.215-.194.215-.194l-.982-.542v5.406h1.843zm5.458-3.09v3.317h-.491V16.34l-.615.615v2.335h-.491v-1.966l-.613.615v.006l-.134.127l.134.052v.457c-.586-.301-1.229.155-1.229.71v1.228h4.053V15.36zm-2.564 3.317h-.036c-.246 0-.215-.328.123-.328c.188 0 .248.101.267.191v.137zm1.315-4.208c0 .152-.051.277-.113.277s-.112-.124-.112-.277s.051-.276.112-.276c.063 0 .113.123.113.276m-1.034.747s.184.175.523.123c.338-.051.45-.358.45-.358s.194.317.409.266c.216-.051.41-.389.41-.389s.01.542-.308.593c-.317.051-.45-.174-.45-.174s-.164.246-.471.266c-.307.022-.563-.327-.563-.327m4.944 3.205l-.265.256h-.43v-3.491l.255-.113l-.992-.573v5.406h1.852z");
}

.vbxe0xtoi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13h36v10H0z");
}

</style>
