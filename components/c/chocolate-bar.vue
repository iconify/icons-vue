<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="orzbzzbzb"/><path class="ckjozsoue"/><path class="x7dvapb6n"/><path class="dnsll-zaj"/><path class="zfstahbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:chocolate-bar" /></template>
<style>
.ckjozsoue {
  fill: var(--svg-color--8a4b38, #8a4b38);
  d: path("m16.582 15.253l-4.885-4.885l5.657-5.657l-1.415-1.414l-5.656 5.657L6.54 5.211L5.126 6.626l3.743 3.742l-5.657 5.657l1.414 1.414l5.657-5.657l4.885 4.885z");
}

.dnsll-zaj {
  fill: var(--svg-color--be1931, #be1931);
  d: path("m12.825 27.053l4.673 4.674l7.955-20.33l-.528-.529l-1.504-.932z");
}

.orzbzzbzb {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M26.339 33.496a4 4 0 0 1-5.657 0L1.59 14.404c-1.562-1.562-1.562-2.681 0-4.243l8.485-8.485c1.562-1.562 2.681-1.562 4.243 0L33.41 20.768a4 4 0 0 1 0 5.657z");
}

.x7dvapb6n {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M26.339 34.91a4 4 0 0 1-5.657 0l-9.899-9.899l14.142-14.142l9.899 9.899a4 4 0 0 1 0 5.657z");
}

.zfstahbjd {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m22.804 8.747l2.121 2.121c-.707 2.122-8.485 15.557-9.9 18.385c0 0-.707 2.121-2.475.354l-5.304-5.304c-.679-.679-.685-2.142 0-2.828L19.975 8.747c1.414-1.414 2.829 0 2.829 0");
}

</style>
