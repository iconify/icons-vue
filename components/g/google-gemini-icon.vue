<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><filter id="SVGqoIxVV2h" width="39.274" height="43.217" x="-19.824" y="13.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="2.46"/></filter><filter id="SVGOahAkcjC" width="84.868" height="85.688" x="-15.001" y="-40.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="11.891"/></filter><filter id="SVGyT4fLePl" width="79.454" height="90.917" x="-20.776" y="11.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="10.109"/></filter><filter id="SVGonSETbRF" width="79.731" height="81.505" x="-19.845" y="15.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="10.109"/></filter><filter id="SVGSN7ofz6B" width="75.117" height="73.758" x="29.832" y="-11.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="9.606"/></filter><filter id="SVGHvbpPvOn" width="78.135" height="78.758" x="-38.583" y="-16.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="8.706"/></filter><filter id="SVG7JmfweRd" width="78.877" height="77.539" x="8.107" y="-5.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="7.775"/></filter><filter id="SVGgGkiybCN" width="56.272" height="51.81" x="13.587" y="-18.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="6.957"/></filter><filter id="SVGxEY6lcrm" width="70.856" height="69.306" x="-15.526" y="-31.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="5.876"/></filter><filter id="SVGMZLCp0yD" width="55.502" height="51.571" x="-14.168" y="20.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_10859_4895" stdDeviation="7.273"/></filter><linearGradient id="SVG1oAMmOOu" x1="18.447" x2="52.153" y1="43.42" y2="15.004" gradientUnits="userSpaceOnUse"><stop class="wm9f5urmk"/><stop offset=".27" class="wm9f5urmk"/><stop offset=".777" class="p4cy2rbkd"/><stop offset="1" class="kiz7ahbwl"/></linearGradient></defs><path class="z4t71eb2m"/><g filter="url(#SVGqoIxVV2h)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(19.552 -44.576 -16.496)" class="ahq-vpb9t"/></g><g filter="url(#SVGOahAkcjC)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse class="cewad35yy"/></g><g filter="url(#SVGyT4fLePl)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(-2.799 18.951 57.386)" class="criwxrnwb"/></g><g filter="url(#SVGyT4fLePl)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(-2.799 18.951 57.386)" class="criwxrnwb"/></g><g filter="url(#SVGonSETbRF)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(-31.318 20.02 56.211)" class="c0gih1b2f"/></g><g filter="url(#SVGSN7ofz6B)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse class="v7p30pgmq"/></g><g filter="url(#SVGHvbpPvOn)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(37.252 9.752 -8.009)" class="ux9fyhcrv"/></g><g filter="url(#SVG7JmfweRd)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(34.51 19.587 64.852)" class="v5671jbsf"/></g><g filter="url(#SVGgGkiybCN)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><path class="q9mcazbrh"/></g><g filter="url(#SVGxEY6lcrm)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(-42.848 19.902 3.356)" class="lf6ybrz4h"/></g><g filter="url(#SVGMZLCp0yD)" mask="url(#SVGWpw6Gcvj)" transform="translate(-.101 -.049)scale(3.9436)"><ellipse transform="rotate(35.592 13.583 46.75)" class="hvwag62ka"/></g><mask id="SVGWpw6Gcvj" width="65" height="65" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="p9ejzub0v"/><path fill="url(#SVG1oAMmOOu)" class="p9ejzub0v"/></mask>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-gemini-icon" /></template>
<style>
.ahq-vpb9t {
  cx: 14.407px;
  cy: 16.95px;
  fill: var(--svg-color--ffe432, #ffe432);
  rx: 14.407px;
  ry: 16.95px;
}

.c0gih1b2f {
  cx: 20.02px;
  cy: 56.211px;
  fill: var(--svg-color--00b95c, #00b95c);
  rx: 19.107px;
  ry: 21.035px;
}

.cewad35yy {
  cx: 27.433px;
  cy: 2.587px;
  fill: var(--svg-color--fc413d, #fc413d);
  rx: 18.652px;
  ry: 19.062px;
}

.criwxrnwb {
  cx: 18.951px;
  cy: 57.386px;
  fill: var(--svg-color--00b95c, #00b95c);
  rx: 19.493px;
  ry: 25.253px;
}

.hvwag62ka {
  cx: 13.583px;
  cy: 46.75px;
  fill: var(--svg-color--ffee48, #ffee48);
  rx: 14.989px;
  ry: 8.717px;
}

.kiz7ahbwl {
  stop-color: var(--svg-color--bd99fe, #bd99fe);
}

.lf6ybrz4h {
  cx: 19.902px;
  cy: 3.356px;
  fill: var(--svg-color--fc413d, #fc413d);
  rx: 27.971px;
  ry: 17.388px;
}

.p4cy2rbkd {
  stop-color: var(--svg-color--969dff, #969dff);
}

.p9ejzub0v {
  d: path("M32.447 0c.68 0 1.273.465 1.439 1.125a39 39 0 0 0 1.999 5.905q3.23 7.5 8.854 13.125q5.627 5.626 13.125 8.855a39 39 0 0 0 5.906 1.999c.66.166 1.124.758 1.124 1.438s-.464 1.273-1.125 1.439a39 39 0 0 0-5.905 1.999q-7.5 3.23-13.125 8.854q-5.625 5.627-8.854 13.125a39 39 0 0 0-2 5.906a1.485 1.485 0 0 1-1.438 1.124c-.68 0-1.272-.464-1.438-1.125a39 39 0 0 0-2-5.905q-3.227-7.5-8.854-13.125q-5.625-5.625-13.125-8.854a39 39 0 0 0-5.905-2A1.485 1.485 0 0 1 0 32.448c0-.68.465-1.272 1.125-1.438a39 39 0 0 0 5.905-2q7.5-3.228 13.125-8.854q5.626-5.624 8.855-13.125a39 39 0 0 0 1.999-5.905A1.485 1.485 0 0 1 32.447 0");
}

.q9mcazbrh {
  fill: var(--svg-color--749bff, #749bff);
  d: path("M54.984-2.336c2.833 3.852-.808 11.34-8.131 16.727s-15.557 6.631-18.39 2.78c-2.833-3.853.807-11.342 8.13-16.728s15.558-6.631 18.39-2.78");
}

.ux9fyhcrv {
  cx: 21.222px;
  cy: 22.384px;
  fill: var(--svg-color--fbbc04, #fbbc04);
  rx: 21.222px;
  ry: 22.384px;
}

.v5671jbsf {
  cx: 24.469px;
  cy: 22.604px;
  fill: var(--svg-color--3186ff, #3186ff);
  rx: 24.469px;
  ry: 22.604px;
}

.v7p30pgmq {
  cx: 67.391px;
  cy: 25.327px;
  fill: var(--svg-color--3186ff, #3186ff);
  rx: 18.346px;
  ry: 17.667px;
}

.wm9f5urmk {
  stop-color: var(--svg-color--4893fc, #4893fc);
}

.z4t71eb2m {
  fill: var(--svg-color--fff, #fff);
  d: path("M228.265 114.441c-19.721-8.49-36.974-20.134-51.776-34.927c-14.792-14.789-26.436-32.056-34.93-51.779a154 154 0 0 1-7.884-23.295A5.86 5.86 0 0 0 127.999 0a5.86 5.86 0 0 0-5.674 4.44a154 154 0 0 1-7.882 23.295c-8.494 19.723-20.141 36.99-34.929 51.779c-14.794 14.793-32.058 26.437-51.779 34.927a154 154 0 0 1-23.297 7.889A5.855 5.855 0 0 0 0 127.999a5.86 5.86 0 0 0 4.438 5.678a154 154 0 0 1 23.297 7.886c19.721 8.49 36.978 20.139 51.779 34.93c14.795 14.789 26.435 32.055 34.929 51.774a154 154 0 0 1 7.882 23.297a5.854 5.854 0 0 0 5.674 4.436a5.85 5.85 0 0 0 5.676-4.436a154 154 0 0 1 7.884-23.297q12.742-29.58 34.93-51.774c14.793-14.791 32.055-26.44 51.776-34.93a154 154 0 0 1 23.297-7.886a5.86 5.86 0 0 0 4.438-5.678a5.855 5.855 0 0 0-4.438-5.669a154.4 154.4 0 0 1-23.297-7.889");
}

</style>
