<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hwcfj9bbi"/><path class="jiks3hb7x"/><path class="wqzg3jbpj"/><path class="h-j2vcb_a"/><path class="krcz9mbyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-chat-linear" /></template>
<style>
.h-j2vcb_a {
  stroke-linejoin: round;
  d: path("M22 9H4");
}

.hwcfj9bbi {
  d: path("M17.8144 21.236L17.5433 21.6939C17.3017 22.102 16.6982 22.102 16.4567 21.6939L16.1856 21.236C15.9754 20.8808 15.8702 20.7032 15.7014 20.605C15.5325 20.5068 15.32 20.5031 14.8948 20.4958C14.2671 20.4849 13.8734 20.4465 13.5433 20.3097C12.9307 20.056 12.444 19.5693 12.1903 18.9567C12 18.4973 12 17.9149 12 16.75V16.25C12 14.6133 12 13.7949 12.3684 13.1938C12.5745 12.8574 12.8574 12.5745 13.1938 12.3684C13.7949 12 14.6133 12 16.25 12H17.75C19.3867 12 20.2051 12 20.8062 12.3684C21.1426 12.5745 21.4255 12.8574 21.6316 13.1938C22 13.7949 22 14.6133 22 16.25V16.75C22 17.9149 22 18.4973 21.8097 18.9567C21.556 19.5693 21.0693 20.056 20.4567 20.3097C20.1266 20.4465 19.7329 20.4849 19.1052 20.4958C18.68 20.5031 18.4674 20.5068 18.2986 20.605C18.1297 20.7032 18.0246 20.8808 17.8144 21.236Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jiks3hb7x {
  stroke-linejoin: round;
  d: path("M10 3L5 21");
}

.krcz9mbyu {
  stroke-linejoin: round;
  d: path("M2 16H9");
}

.wqzg3jbpj {
  stroke-linejoin: round;
  d: path("M18.9999 3L17.1943 9.5");
}

</style>
