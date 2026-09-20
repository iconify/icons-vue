<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w0icm7bdc"/><path clip-rule="evenodd" class="xwpcc3sdm"/><path clip-rule="evenodd" class="ks5a5qb8y"/><path clip-rule="evenodd" class="xexlxy-cc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bta-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ks5a5qb8y {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.695a7.709 7.709 0 1 0 0-15.418a7.709 7.709 0 0 0 0 15.418m0-.302a7.46 7.46 0 1 0-7.459-7.463a7.46 7.46 0 0 0 7.46 7.459z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w0icm7bdc {
  fill: var(--svg-color--549f4c, #549f4c);
  d: path("M24 0H0v24h24z");
}

.xexlxy-cc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-8 7.797a7.81 7.81 0 0 0 7.217-10.8A7.815 7.815 0 0 0 12 4.173a7.812 7.812 0 0 0 0 15.624");
}

.xwpcc3sdm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.29a7.355 7.355 0 1 0 0-14.71a7.355 7.355 0 0 0 0 14.71m-1.75-4.324a3 3 0 0 1-.311-.98c-.088-.858-.123-1.717-.159-2.578l-.025-.602l-.014-.626l-.007-.442c-.013-.902-.027-1.814.021-2.711a.047.047 0 0 1 .047-.047q.284-.04.563-.073c.26-.031.516-.062.774-.106q.02-.001.018.019c.02 2.155.066 4.306.207 6.46c.01.194.024.406.076.584c.141.518.466.88.96 1.073c.202.08.41.075.621.062c.325-.037.626-.187.852-.424a.047.047 0 0 1 .066 0l1.115 1.035q.015.017 0 .024a5 5 0 0 1-.706.602a2.67 2.67 0 0 1-1.59.414a2 2 0 0 1-1.186-.292l-.109-.065a2.3 2.3 0 0 1-.386-.269a2.8 2.8 0 0 1-.828-1.058m3.91-.824c.282-.673.183-1.412-.33-1.939a1.36 1.36 0 0 0-.983-.4q-.683.036-1.365.099q-.036-.812-.061-1.623c0-.01.005-.02.019-.02a55 55 0 0 1 1.308-.122c.466-.033.918.038 1.341.236a3.04 3.04 0 0 1 1.685 2.089c.103.626.141 1.224-.024 1.85a3.8 3.8 0 0 1-.555 1.12h-.005l-1.115-1.055a.05.05 0 0 1-.01-.066c.034-.047.067-.108.095-.169m-4.57-2.315q-.007-.344-.037-.697q-.009-.115-.011-.25a5 5 0 0 0-.022-.385a.07.07 0 0 0-.023-.045a.07.07 0 0 0-.048-.016l-1.346.136l-.032.003c-.096.009-.26.024-.26.124c-.009.42.005.89.038 1.421c0 .057.028.08.085.08a31 31 0 0 1 1.548-.136c.108 0 .108-.15.108-.235");
}

</style>
